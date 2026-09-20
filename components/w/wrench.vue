<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="d2pue8mfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:wrench" /></template>
<style>
.d2pue8mfs {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M27.989 19.977c-.622 0-1.225.078-1.806.213L15.811 9.818a8 8 0 0 0 .212-1.806A8.01 8.01 0 0 0 8.012 0C7.11 0 5.91.916 6.909 1.915l2.997 2.997s.999 1.998-.999 3.995s-3.996.998-3.996.998L1.915 6.909C.916 5.91 0 7.105 0 8.012a8.01 8.01 0 0 0 8.012 8.012a8 8 0 0 0 1.806-.212l10.371 10.371a8 8 0 0 0-.213 1.806A8.01 8.01 0 0 0 27.988 36c.901 0 2.101-.916 1.102-1.915l-2.997-2.997s-.999-1.998.999-3.995s3.995-.999 3.995-.999l2.997 2.997c1 .999 1.916-.196 1.916-1.102a8.01 8.01 0 0 0-8.011-8.012");
}

</style>
