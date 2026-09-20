<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quzyad86c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-play-sharp" /></template>
<style>
.quzyad86c {
  fill: currentColor;
  d: path("M9 3V1h6v2zm-.488 18.288q-1.637-.713-2.862-1.938t-1.937-2.863T3 13t.713-3.488T5.65 6.65t2.863-1.937T12 4q1.55 0 2.975.5t2.675 1.45l1.4-1.4l1.4 1.4l-1.4 1.4Q20 8.6 20.5 10.025T21 13q0 1.85-.713 3.488T18.35 19.35t-2.863 1.938T12 22t-3.488-.712M10 17l6-4l-6-4z");
}

</style>
