<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jsd971b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:smiley-nervous" /></template>
<style>
.jsd971b-p {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88M80 108a12 12 0 1 1 12 12a12 12 0 0 1-12-12m72 0a12 12 0 1 1 12 12a12 12 0 0 1-12-12m32 60a8 8 0 0 1-8 8c-10 0-15.06-6.74-18.4-11.2c-3-4-3.92-4.8-5.6-4.8s-2.57.76-5.6 4.8c-3.34 4.46-8.4 11.2-18.4 11.2s-15.06-6.74-18.4-11.2c-3-4-3.92-4.8-5.6-4.8s-2.57.76-5.6 4.8C95.06 169.26 90 176 80 176a8 8 0 0 1 0-16c1.68 0 2.57-.76 5.6-4.8C88.94 150.74 94 144 104 144s15.06 6.74 18.4 11.2c3 4 3.92 4.8 5.6 4.8s2.57-.76 5.6-4.8c3.34-4.46 8.4-11.2 18.4-11.2s15.06 6.74 18.4 11.2c3 4 3.92 4.8 5.6 4.8a8 8 0 0 1 8 8");
}

</style>
