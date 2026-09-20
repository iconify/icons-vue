<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owuglzbel.css';
import '../../css/f/f0zfi2mjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owuglzbel"/><path class="f0zfi2mjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-notes-music-2" /></template>
