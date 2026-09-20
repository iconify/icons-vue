<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-rzh3b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-10-alt-1-sharp" /></template>
<style>
.m-rzh3b3u {
  fill: currentColor;
  d: path("M8.25 17.25h2v-8.5h-3v2h1zm3 0h5.5v-8.5h-5.5zm2-2v-4.5h1.5v4.5zM9 3V1h6v2zm-.488 18.288q-1.637-.713-2.862-1.938t-1.937-2.863T3 13t.713-3.488T5.65 6.65t2.863-1.937T12 4q1.55 0 2.975.5t2.675 1.45l1.4-1.4l1.4 1.4l-1.4 1.4Q20 8.6 20.5 10.025T21 13q0 1.85-.713 3.488T18.35 19.35t-2.863 1.938T12 22t-3.488-.712");
}

</style>
