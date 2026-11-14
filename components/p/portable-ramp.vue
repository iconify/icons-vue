<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyy1fjher"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:portable-ramp" /></template>
<style>
.qyy1fjher {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.164 11.205q.086.354.086.795q0 2.25-2.25 2.25q-.757 0-1.259-.255L4.527 16.75H14.75V8.131zm-4.328 1.59Q6.75 12.441 6.75 12q0-2.25 2.25-2.25q.757 0 1.259.255l4.752-4.074h.001l.015-.013q.101-.082.222-.125q.122-.043.251-.043h6q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v11q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19l-.055-.002h-.003q-.133-.011-.255-.067t-.217-.151q-.021-.02-.039-.042q-.088-.102-.134-.228t-.047-.26q0-.149.057-.287t.163-.243q.02-.021.042-.039zm9.414 3.955h4.5v-9.5h-4.5z");
}

</style>
