<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq3vmcb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unknown-med-outline" /></template>
<style>
.iq3vmcb7a {
  fill: currentColor;
  d: path("M4 12.5q-.417 0-.708-.291Q3 11.918 3 11.502t.292-.709T4 10.5h6q.417 0 .708.291q.292.291.292.707t-.292.709T10 12.5zm9.98 0q-.416 0-.707-.291q-.292-.291-.292-.707t.292-.709t.708-.293h6q.416 0 .708.291t.292.707t-.292.709t-.708.293z");
}

</style>
