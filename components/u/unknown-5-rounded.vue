<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_s93xbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unknown-5-rounded" /></template>
<style>
.g_s93xbhc {
  fill: currentColor;
  d: path("M5.5 12q-.213 0-.356-.144T5 11.499t.144-.356T5.5 11h6q.213 0 .356.144t.144.357t-.144.356T11.5 12zM12 4q-.213 0-.356-.144t-.144-.357t.144-.356T12 3q1.872 0 3.507.71q1.635.711 2.853 1.93t1.93 2.855t.71 3.5t-.71 3.505t-1.93 2.86t-2.853 1.93T12 21q-1.79 0-3.434-.67T5.63 18.37q-.061-.064-.104-.158q-.043-.095-.043-.196q0-.214.145-.357t.359-.143q.1 0 .194.042t.156.104q1.175 1.1 2.631 1.719T12 20q3.325 0 5.663-2.337T20 12t-2.337-5.663T12 4");
}

</style>
