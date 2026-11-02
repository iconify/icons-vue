<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-el9mbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-bulk" /></template>
<style>
.r-el9mbko {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m8.293 7.293l4-4c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v6h4c.203-.001.402.047.582.14c.712.371.835 1.242.549 1.932a2 2 0 0 1-.424.635l-8 8a2 2 0 0 1-.635.424c-.69.286-1.561.163-1.932-.549A1.25 1.25 0 0 1 9 20v-6H5a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635Z");
}

</style>
