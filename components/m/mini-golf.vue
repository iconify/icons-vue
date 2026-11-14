<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omssm4bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mini-golf" /></template>
<style>
.omssm4bqu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.75 3.143V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q11.074 2.25 11 2.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T10.25 3v13.29q-6 .29-6 2.71q0 2.75 7.75 2.75T19.75 19T12 16.25l-.25.001V8.857q.789.3 1.636-.064l1.692-.724Q16.443 7.484 16.443 6t-1.365-2.068l-1.692-.725q-.847-.364-1.636-.064");
}

</style>
