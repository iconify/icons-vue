<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":277};
const content = `<path class="bg17mhb7c"/><path class="qyzx5zbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vueuse" /></template>
<style>
.bg17mhb7c {
  fill: var(--svg-color--35495e, #35495e);
  d: path("M202.968 0v148.146c0 41.405-33.563 74.967-74.968 74.967s-74.968-33.562-74.968-74.967V0h53.036v148.146a21.932 21.932 0 1 0 43.864 0V0z");
}

.qyzx5zbrf {
  fill: var(--svg-color--41b883, #41b883);
  d: path("M256 0v148.146c0 70.694-57.306 128.019-128 128.019S0 218.84 0 148.145V0h53.032v148.146c0 41.405 33.566 74.967 74.968 74.967s74.968-33.562 74.968-74.967V0z");
}

</style>
