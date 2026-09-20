<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-6wmh33g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-6wmh33g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:music-note-1-flat" /></template>
