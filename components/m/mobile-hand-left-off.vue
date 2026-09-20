<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4-eoubvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-left-off" /></template>
<style>
.v4-eoubvd {
  fill: currentColor;
  d: path("m20.84 22.78l-2.313-2.313q-.2.24-.495.387q-.295.146-.647.146h-5.17l3.047-3.798l-1.714-1.713l-3.852 4.844q-.275.35-.658.508q-.384.159-.815.159h-.992q-1.25 0-2.125-.875T4.23 18v-7.48q0-.87.466-1.599q.467-.729 1.205-1.085L1.623 3.558l.708-.708l19.223 19.223zM19 16.72L7.923 5.661V4.616q0-.672.472-1.144T9.54 3h7.846q.67 0 1.143.472q.472.472.472 1.144zm-4.999-9.642q.23-.23.23-.54T14 6t-.54-.23q-.309 0-.539.23t-.23.54t.23.539q.23.23.54.23t.539-.23m-5.847 9.48l4.335-2.13l-4.335-4.34z");
}

</style>
