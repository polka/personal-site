<template>
  <svg viewBox="0 0 24 24">
    <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z" />
  </svg>
</template>

<script>
export default {
  name: 'TwitterSvg',
};
</script>

<style lang="scss" scoped>
svg {
  width: 25px;
  height: 25px;
  margin: 16px 0 16px 16px;
}

path {
  fill: none;
  stroke: #b0b5b3;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: 2px;
}
</style>
