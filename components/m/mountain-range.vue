<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrst9rbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mountain-range" /></template>
<style>
.rrst9rbav {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m1.829 19.665l5.5-11q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.179.089.289.255l3.239 4.858l2.95-6.743q.06-.136.167-.24t.247-.157q.139-.055.288-.052t.286.063q.126.055.224.151q.098.097.156.222l6 13q.062.135.068.284t-.045.289t-.153.25t-.237.172q-.149.069-.314.069h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 20q0-.177.079-.335");
}

</style>
