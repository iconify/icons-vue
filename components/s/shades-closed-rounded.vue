<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4uwgnb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shades-closed-rounded" /></template>
<style>
.n4uwgnb9v {
  fill: currentColor;
  d: path("M11.84 21.02q-.236 0-.435-.135q-.2-.133-.31-.345q-.42-.784-1.175-1.268q-.754-.483-1.69-.483q-.984 0-1.787.486q-.802.487-1.227 1.29q-.112.212-.311.333q-.2.121-.416.121h-.104q-.194 0-.309-.114t-.114-.309L3.98 4h-.506q-.194 0-.334-.143Q3 3.713 3 3.5q0-.194.143-.347Q3.287 3 3.5 3h17q.194 0 .347.153T21 3.5q0 .214-.153.357T20.5 4h-.48v16.577q0 .194-.125.318t-.318.124h-.115q-.218 0-.42-.133q-.202-.134-.313-.345q-.425-.804-1.225-1.278t-1.754-.475q-.965 0-1.727.484t-1.186 1.269q-.112.211-.302.344q-.189.134-.426.134zM12.5 4h-1v13.862h1z");
}

</style>
