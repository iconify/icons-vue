<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2160bc5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pregnant-woman" /></template>
<style>
.j2160bc5c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 4.75q0-1.243.878-2.122q.879-.879 2.122-.879t2.122.879t.878 2.122q.001 1.243-.878 2.122q-.848.848-2.035.878h.913q1.961 0 2.478 2.068l.148.595q4.332 1.469 3.868 5.18q-.469 3.288-3.8 3.211l-.196 2.749q-.005.071-.023.139t-.048.132q-.031.063-.073.12t-.093.105t-.111.086q-.06.037-.125.063q-.066.026-.135.039q-.07.013-.14.013H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.326q-1.411-2.934-.994-6.267l.004-.03Q6.781 7.75 8.5 7.75h1.913q-1.187-.03-2.035-.878Q7.5 5.993 7.5 4.75");
}

</style>
