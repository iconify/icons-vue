<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-fmcnk6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:motion-photos-on-rounded" /></template>
<style>
.d-fmcnk6f {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.701t-2.857-1.916t-1.926-2.849Q3 13.902 3 12.04q0-.762.125-1.504q.125-.743.356-1.48q.067-.207.262-.296q.196-.09.373-.005q.201.085.277.299t.009.428q-.188.627-.295 1.257T4 12q0 3.35 2.325 5.675T12 20t5.675-2.325T20 12t-2.325-5.675T12 4q-.639 0-1.255.097t-1.21.291q-.214.068-.416-.015t-.3-.265t-.012-.369q.085-.185.274-.253q.673-.236 1.377-.361T11.885 3q1.882 0 3.544.701t2.896 1.926t1.955 2.867T21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21M5.303 6.543q-.264-.264-.264-.62t.264-.62t.62-.264t.62.264t.265.62t-.265.62t-.62.265t-.62-.265M7.75 7.75Q9.5 6 12 6t4.25 1.75T18 12t-1.75 4.25T12 18t-4.25-1.75T6 12t1.75-4.25");
}

</style>
