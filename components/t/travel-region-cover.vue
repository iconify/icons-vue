<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flsbcrbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:travel-region-cover" /></template>
<style>
.flsbcrbdi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.789 4.446l4.5-1.5q.711-.236 1.422 0l5.052 1.684q.237.079.474 0l3.552-1.184q1.093-.363 2.027.31t.934 1.825v11.838q0 1.622-1.539 2.135l-4.5 1.5q-.711.236-1.422 0L9.237 19.37q-.237-.079-.474 0l-3.552 1.184q-1.093.363-2.027-.31t-.934-1.825V6.581q0-1.622 1.539-2.135M12.01 10H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12.01 10");
}

</style>
