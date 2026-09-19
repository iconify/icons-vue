<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cdhtlqbkg"/><circle class="oclompb7u"/><circle class="pav6vtoat"/><path class="k1e_nobly"/><circle class="mvbrhwg_a"/><circle class="ry6tsxfog"/><circle class="da7chunho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-shower" /></template>
<style>
.cdhtlqbkg {
  cx: 8px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.da7chunho {
  cx: 16px;
  cy: 20px;
  r: 1px;
  fill: currentColor;
}

.k1e_nobly {
  fill: currentColor;
  d: path("M13 5.08V4c0-.55-.45-1-1-1s-1 .45-1 1v1.08C7.61 5.57 5 8.47 5 12v1c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-1c0-3.53-2.61-6.43-6-6.92");
}

.mvbrhwg_a {
  cx: 8px;
  cy: 20px;
  r: 1px;
  fill: currentColor;
}

.oclompb7u {
  cx: 12px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.pav6vtoat {
  cx: 16px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.ry6tsxfog {
  cx: 12px;
  cy: 20px;
  r: 1px;
  fill: currentColor;
}

</style>
