<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pcp9msbrq"/><g class="fzhes4buc"><path class="iblwte62z"/><path class="ov7jrehvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:map-of-japan" /></template>
<style>
.fzhes4buc {
  fill: var(--svg-color--3e721d, #3e721d);
}

.iblwte62z {
  d: path("M24 2c1 0 2 3 3 3s3 0 3 1s-3 1-3 2s-1 1-2 1s-3 0-3-1s2 0 2-1s-1-5 0-5m-3 8c0-1 2-1 2-1s1 2 0 2s-2-1-2-1m2 2c-1 0-1 2-1 3s0 3-1 3s-2 1-2 2s-1 2-2 2s-2 2-2 2s-4 1-5 1s-3 0-3 1s-3 2-1 2s2-1 3-1h2s3-1 3 0s0 2 1 2s2-1 2-2s1-1 2-1s2 0 2-1s1-2 2-2s1-2 1-3s0-3 1-3s2-3 1-3s-2 0-2-1s-1-1-1-1");
}

.ov7jrehvi {
  d: path("M8 30c0-1 0-2 1-2h3c1 0 1 0 0 1s-1 0-2 0s0 2-1 2s-1-1-1-1m-4 3c0-1 1-1 1-2s-1 0-1-1s1-1 2-1s1 1 1 2s-1 1-1 2s-1 1-1 1s-1 0-1-1");
}

.pcp9msbrq {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M36 32s0 4-4 4H4s-4 0-4-4V4c0-4 4-4 4-4h28c4 0 4 4 4 4z");
}

</style>
