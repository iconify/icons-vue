<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu1-3nqdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-wifi-statusbar-not-connected-outline-sharp" /></template>
<style>
.mu1-3nqdl {
  fill: currentColor;
  d: path("M12 19.577L1.423 9q2.183-1.964 4.91-2.982Q9.063 5 12 5t5.666 1.018Q20.394 7.037 22.577 9l-.538.539q-.662-.555-1.401-.855T19 8.385q-1.921 0-3.268 1.357T14.385 13q0 .956.338 1.753q.339.797.816 1.286zm6.513-.678q-.179-.178-.179-.449t.178-.449t.45-.178q.27 0 .449.178q.178.178.178.449t-.178.449t-.45.178q-.27 0-.448-.178m.006-2.099q0-.892.231-1.388q.23-.497.998-1.303q.487-.486.685-.835t.198-.71q0-.527-.37-.98q-.369-.453-1.174-.453q-.64 0-1.081.347t-.698.826l-.812-.358q.339-.68 1.004-1.179q.666-.498 1.587-.498q1.07 0 1.75.629t.679 1.677q0 .575-.25 1.006t-.989 1.169q-.542.542-.702.934q-.16.391-.16 1.116z");
}

</style>
