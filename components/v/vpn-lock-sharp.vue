<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsz5cy6ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vpn-lock-sharp" /></template>
<style>
.hsz5cy6ry {
  fill: currentColor;
  d: path("M8.48 20.299q-1.641-.701-2.86-1.92t-1.919-2.86T3 11.997q0-1.88.701-3.519t1.92-2.858t2.86-1.919T12 3q.8 0 1.538.132T15 3.488V7h-4v3H8v2h7v4h1l1.9 1.4q.975-1.061 1.538-2.443T20 12q0-.275-.006-.5t-.055-.5h1.011q.05.275.05.5v.5q0 1.877-.701 3.52t-1.92 2.86t-2.857 1.919t-3.519.701t-3.522-.701M11 19.95V18l-2-2v-1l-4.8-4.8q-.075.45-.137.9T4 12q0 3.062 2.013 5.318T11 19.95M17 9V4.462h1v-1q0-.749.51-1.259q.511-.51 1.26-.51t1.258.51q.51.51.51 1.259v1h1V9zm1.77-4.538h2v-1q0-.425-.288-.713t-.713-.287t-.712.287t-.288.713z");
}

</style>
