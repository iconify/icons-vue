<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwsjnub-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:update-outline-rounded" /></template>
<style>
.kwsjnub-y {
  fill: currentColor;
  d: path("M12.02 20q-1.664 0-3.119-.626T6.359 17.66t-1.714-2.542T4.02 12t.626-3.118T6.36 6.34T8.9 4.626T12.019 4q1.723 0 3.282.712q1.559.711 2.718 1.984V4.808q0-.214.144-.357t.356-.143t.357.143t.143.357v2.846q0 .348-.23.578t-.578.23h-2.845q-.214 0-.357-.144t-.143-.357t.143-.356t.357-.144h1.98q-1.044-1.15-2.41-1.805Q13.572 5 12.02 5Q9.094 5 7.057 7.038T5.019 12t2.038 4.963T12.019 19q2.472 0 4.375-1.55t2.447-3.934q.067-.228.228-.35q.162-.124.37-.093q.232.03.338.218t.044.409q-.571 2.764-2.746 4.532T12.019 20m.5-8.208l3 3q.14.14.15.344q.01.205-.15.364q-.16.16-.354.16t-.353-.16l-3.05-3.05q-.131-.13-.187-.27t-.056-.301V7.5q0-.213.144-.357T12.019 7t.357.143t.143.357z");
}

</style>
