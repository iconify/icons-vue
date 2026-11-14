<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc5gnvbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scene-mesh" /></template>
<style>
.hc5gnvbdl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m1.97 7.47l5.5-5.5q.105-.106.243-.163T8 1.75h13.5q.149 0 .287.057t.243.163l.007.007q.103.105.158.24q.055.136.055.283V16q0 .149-.057.287t-.163.243l-5.5 5.5q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113L3.03 7.47q-.105-.106-.243-.163T2.5 7.25t-.287.057t-.243.163m-.061.992Q1.75 8.901 1.75 9.5V20q0 2.25 2.25 2.25h10.5q.599 0 1.038-.159q-.036-.028-.068-.061L1.97 8.53q-.033-.032-.061-.068m17.78-5.212H8.311l-4 4H14.5q.595 0 1.032.157zm-3.096 5.218q.157.437.157 1.032v10.189l4-4V4.311z");
}

</style>
