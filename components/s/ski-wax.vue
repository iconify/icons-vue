<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8bmkccio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ski-wax" /></template>
<style>
.w8bmkccio {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 10.25H5q-.061 0-.12-.01q-.06-.009-.118-.029q-.057-.019-.111-.047q-.053-.028-.102-.065q-.048-.036-.09-.08t-.077-.093q-.034-.05-.06-.105t-.043-.113q-.029.183-.029.378V19.5q0 2.25 2.25 2.25h6.094q.132 0 .26-.014q-.063-.013-.124-.036q-.06-.023-.115-.057q-.056-.033-.105-.075t-.09-.092t-.072-.106t-.054-.117t-.033-.125T12.25 21zm1.247 11.312q.117-.052.231-.118l4.906-2.862q1.116-.652 1.116-1.944V4.5q0-.599-.159-1.038q-.019.024-.04.047L13.75 9.793V21q0 .161-.066.308q-.067.147-.187.254M12.672 8.75l5.777-6.259q.041-.044.089-.082q-.439-.159-1.038-.159h-5.843q-.985 0-1.653.724L4.847 8.56q-.132.144-.235.298q.179-.108.388-.108z");
}

</style>
