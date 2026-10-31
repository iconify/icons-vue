<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnd2b7bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnd2b7bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-fill-round" /></template>
