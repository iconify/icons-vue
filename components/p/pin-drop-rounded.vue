<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua-vdxvod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-drop-rounded" /></template>
<style>
.ua-vdxvod {
  fill: currentColor;
  d: path("M11.493 17.704q-.246-.09-.45-.271q-2.49-2.216-3.766-4.348Q6 10.955 6 9.016q0-2.644 1.68-4.33Q9.362 3 12 3t4.32 1.686Q18 6.37 18 9.016q0 1.938-1.277 4.06t-3.766 4.348q-.21.19-.453.28t-.504.09t-.507-.09m.51-7.089q.668 0 1.14-.475q.472-.476.472-1.143t-.475-1.14t-1.144-.472t-1.14.475t-.472 1.144t.476 1.14t1.143.472M6.5 21q-.213 0-.356-.144T6 20.499t.144-.356T6.5 20h11q.213 0 .356.144t.144.357t-.144.356T17.5 21z");
}

</style>
