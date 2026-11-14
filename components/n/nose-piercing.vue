<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv4eyu9qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nose-piercing" /></template>
<style>
.kv4eyu9qt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.718 2.284q1.294 4.314 8.616 10.644q.776.672 1.16 1.008q.019.016.036.034q1.477 1.477.715 3.153q-.265.584-.693.958q.448.61.448 1.669q0 2.5-2.5 2.5t-2.5-2.5q0-.564.127-1H11.5q-1.092 0-1.721-.851q-.534-.725-.465-1.702Q9.489 13.75 12 13.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-1.114 0-1.189 1.053q-.031.426.175.705q.179.242.514.242h4q1.04 0 1.38-.748q.328-.722-.394-1.455q-.38-.333-1.133-.984Q7.701 7.447 6.282 2.716q-.043-.143-.028-.292q.015-.148.086-.28q.07-.131.186-.225q.116-.095.258-.137t.292-.028q.148.015.28.086q.131.07.225.186q.095.116.137.258");
}

</style>
