<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vbnv1kbxq.css';
import '../../css/d/dgtoqqfwz.css';
import '../../css/r/rwolggbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vbnv1kbxq"/><path class="dgtoqqfwz"/><path class="rwolggbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:x-ray" /></template>
