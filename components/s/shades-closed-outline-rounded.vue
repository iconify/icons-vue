<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ups7a6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shades-closed-outline-rounded" /></template>
<style>
.d9ups7a6k {
  fill: currentColor;
  d: path("M11.84 21.02q-.236 0-.435-.135q-.2-.133-.31-.345q-.42-.784-1.175-1.268q-.754-.483-1.69-.483q-.984 0-1.787.486q-.802.487-1.227 1.29q-.112.212-.311.333q-.2.121-.416.121h-.104q-.194 0-.309-.114t-.114-.309L3.98 4h-.506q-.194 0-.334-.143Q3 3.713 3 3.5q0-.194.143-.347Q3.287 3 3.5 3h17q.194 0 .347.153T21 3.5q0 .214-.153.357T20.5 4h-.48v16.577q0 .194-.125.318t-.318.124h-.115q-.218 0-.42-.133q-.202-.134-.313-.345q-.425-.804-1.225-1.278t-1.754-.475q-.965 0-1.727.484t-1.186 1.269q-.112.211-.302.344q-.189.134-.426.134zm-6.86-1.745q.484-.575 1.195-.954t1.537-.465V4H4.98zm3.732-1.413q.857.086 1.579.513q.72.427 1.209 1.098V4H8.711zm3.788 1.573q.483-.658 1.194-1.072t1.575-.501V4H12.5zm6.52-.135V4h-2.75v13.862q.819.086 1.53.462t1.22.976M7.711 4H4.98zM11.5 4H8.711zm3.77 0H12.5zm3.75 0h-2.75zM12.5 4h-1z");
}

</style>
