<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odcnkpbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-hockey" /></template>
<style>
.odcnkpbmd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.305 2.217q.043-.104.113-.19t.164-.149q.092-.063.199-.095q.107-.033.219-.033h3q.114 0 .224.034q.07.022.135.058q.065.035.122.082q.056.048.103.105q.046.058.08.123q.035.065.055.136q.021.071.028.145q.007.073-.001.147q-.008.073-.03.144l-5 16l-.008.025q-.558 1.585-2.228 1.501H4.5q-1.75 0-1.75-1.75V17q0-1.75 1.75-1.75h3.496zM18.25 14q-4 0-4 2.5v2q0 2.5 4 2.5q1.535 0 2.654-.602q1.346-.725 1.346-1.898v-2q0-1.173-1.346-1.898Q19.785 14 18.25 14m2.5 4.477v.023q0 1-2.5 1q-2.334 0-2.489-.871q.948.371 2.489.371q1.431 0 2.5-.523");
}

</style>
