<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucd-cubam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ucd-cubam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-note-off-2-remix" /></template>
