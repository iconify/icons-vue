<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7lyx7bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:spatial-gallery-outline-rounded" /></template>
<style>
.l7lyx7bed {
  fill: currentColor;
  d: path("M9.673 16.337h4.654V12.5H9.673zm0-4.837h4.654V7.727H9.673zM4 11.5h4.673V7.71L4 6.323zm0 6.183l4.673-1.293V12.5H4zm16 0V12.5h-4.673v3.89zM15.327 11.5H20V6.423l-4.673 1.204zm-.442 5.837h-5.77L4.02 18.733q-.378.106-.699-.137Q3 18.354 3 17.95V6.075q0-.404.32-.653t.705-.124L9.096 6.75h5.789l5.096-1.377q.379-.106.699.137q.32.242.32.646V17.95q0 .404-.32.646t-.7.137z");
}

</style>
