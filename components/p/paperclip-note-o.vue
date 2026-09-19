<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc49rjbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="dc49rjbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:paperclip-note-o" /></template>
