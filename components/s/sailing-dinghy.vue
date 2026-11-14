<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjdt-xqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sailing-dinghy" /></template>
<style>
.gtjdt-xqy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.75 13.5v1.25h7.392q1.212 0 1.799 1.06t-.055 2.088l-.809 1.294q-.661 1.058-1.908 1.058H6.681q-1.021 0-1.693-.768l-1.302-1.488q-.83-.949-.309-2.097q.521-1.147 1.781-1.147h5.092V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.209l7.804 8.535q.049.054.088.118q.038.063.063.132q.025.07.036.143q.012.073.008.147q-.003.073-.021.145q-.017.072-.049.139q-.031.067-.075.126q-.043.06-.098.11q-.104.094-.235.145T19 13.5zm0-1.5h5.548L11.75 5.932zM9 9.125v2.125q0 2.25-2.25 2.25h-.875q-1.213 0-1.789-1.067q-.577-1.067.089-2.082l1.461-2.23q.748-1.142 2.056-.751T9 9.125");
}

</style>
