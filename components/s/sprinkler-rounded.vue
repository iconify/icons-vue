<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6cw9m4ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sprinkler-rounded" /></template>
<style>
.g6cw9m4ys {
  fill: currentColor;
  d: path("M11.46 11.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m0-4q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m0-4q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m3 10q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m2.826-2.85q-.23-.23-.23-.54t.23-.54t.539-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m2.826-2.8q-.23-.23-.23-.54t.23-.54t.539-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23M8.46 13.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m-2.824-2.85q-.23-.23-.23-.54t.23-.54t.539-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m-2.824-2.8q-.23-.23-.23-.54t.23-.54t.539-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m8.69 9.61H8q-.213 0-.357-.143T7.5 17t.143-.357T8 16.5h8q.214 0 .357.143T16.5 17t-.143.357T16 17.5h-3.5V21q0 .214-.143.357T12 21.5t-.357-.143T11.5 21z");
}

</style>
