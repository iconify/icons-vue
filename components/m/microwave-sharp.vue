<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9-123ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:microwave-sharp" /></template>
<style>
.k9-123ble {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h11V6H4zm13.308-9.308h1.384V7.308h-1.384zM18 12.77q.31 0 .54-.23t.23-.539t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m0 4q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m-7.25-1.27q-.484 0-.893-.215q-.409-.216-.695-.397q-.27-.175-.468-.281T8.25 14.5q-.256 0-.502.129t-.429.279l-.732-.708q.275-.223.704-.461q.43-.239.959-.239q.485 0 .865.209q.38.208.666.389q.263.189.505.295t.464.107q.256 0 .502-.129t.429-.279l.733.708q-.275.223-.705.462q-.43.238-.959.238m0-5q-.484 0-.893-.215q-.409-.216-.695-.397q-.27-.175-.468-.281T8.25 9.5q-.256 0-.502.129t-.429.279L6.587 9.2q.275-.223.704-.461q.43-.239.959-.239q.485 0 .865.209q.38.208.666.389q.263.189.505.295t.464.107q.256 0 .502-.129t.429-.279l.733.708q-.275.223-.705.462q-.43.238-.959.238");
}

</style>
