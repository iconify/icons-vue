<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl2wje-dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-up-alt-rounded" /></template>
<style>
.fl2wje-dc {
  fill: currentColor;
  d: path("M8.463 18.538Q7 17.075 7 15q0-1.825 1.138-3.187T11 10.1V5.825l-.9.9Q9.825 7 9.413 7T8.7 6.7q-.275-.275-.275-.7t.275-.7l2.6-2.6q.15-.15.325-.213T12 2.426t.375.063t.325.212l2.6 2.6q.275.275.275.688T15.3 6.7q-.3.3-.712.3t-.713-.3L13 5.825V10.1q1.725.35 2.863 1.713T17 15q0 2.075-1.463 3.538T12 20t-3.537-1.463");
}

</style>
