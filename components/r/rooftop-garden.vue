<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7128lzld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rooftop-garden" /></template>
<style>
.l7128lzld {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.787 4.781Q13.008 2.25 17 2.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.896-5 5.226v3.024h5.5q2.5 0 2.5 2.5v6q0 1.036-.732 1.768t-1.768.732H5.75q-1.036 0-1.768-.732T3.25 19.75v-6q0-2.5 2.5-2.5h5.5V9.726q-5-.33-5-5.226q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 3.75 7 3.75q2.924 0 4.361 1.357q.073-.118.183-.202t.243-.124");
}

</style>
