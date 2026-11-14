<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqccypbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ring-tray" /></template>
<style>
.zqccypbbs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.193 3.111Q8.753 2.5 8 2.5t-1.193.611q-.441.611-.202 1.326l.183.55q.119.356.342.566Q4 5.962 4 9.5q0 3 2.25 3.75H5.125q-1.398 0-2.386.989q-.989.988-.989 2.386v2.25q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-2.25q0-3.375-3.375-3.375H17.75Q20 12.5 20 9.5q0-3.538-3.129-3.947q.222-.21.34-.565l.185-.552q.238-.714-.203-1.325Q16.753 2.5 16 2.5t-1.193.611t-.202 1.326l.183.55q.119.356.342.566Q12 5.962 12 9.5q0-3.538-3.129-3.947q.222-.21.34-.565l.185-.552q.238-.714-.203-1.325M12 9.5q0 3 2.25 3.75h-4.5Q12 12.5 12 9.5");
}

</style>
