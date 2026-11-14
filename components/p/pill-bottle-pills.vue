<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_xu38bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pill-bottle-pills" /></template>
<style>
.j_xu38bqk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 3.25H4q-2.25 0-2.25 2.25v5q0 2.25 2.25 2.25h6.5q.132 0 .255-.045q.124-.045.225-.129l2.792-2.326H16.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.728L10.98 3.424q-.101-.084-.225-.129q-.123-.045-.255-.045m7 10.25q0-2.5 2.5-2.5t2.5 2.5T20 16t-2.5-2.5M9 19q0-2.5 2.5-2.5T14 19t-2.5 2.5T9 19m8.75-2q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5");
}

</style>
