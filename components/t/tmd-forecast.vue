<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v0_7g92lj"/><path class="zj1-unf0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tmd-forecast" /></template>
<style>
.v0_7g92lj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.07 17.409c.103-.449.154-.907.154-1.364c0-3.678-3.286-6.66-7.34-6.66a8 8 0 0 0-2.46.405c-.897-3.092-4.442-5.29-8.534-5.29c-4.082.006-7.616 2.198-8.517 5.282a7 7 0 0 0-.257-.006c-4.054 0-7.34 2.981-7.34 6.66q0 .489.078.972z");
}

.zj1-unf0q {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.927 43.5l-.038-26.091");
}

</style>
