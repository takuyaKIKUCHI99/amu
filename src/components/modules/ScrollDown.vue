<template>
  <i class="fas fa-angle-double-down" @click="$emit('scrollDown')"></i>
</template>

<script>
export default {
  name: "ScrollDown"
};
</script>

<style scoped lang="scss">
i {
  color: rgba(255, 255, 255, 0.8);
  font-size: 2rem;
  position: absolute;
  bottom: 16px;
  left: 16px;
}
</style>
