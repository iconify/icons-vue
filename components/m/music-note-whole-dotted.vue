<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkyld3bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkyld3bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-whole-dotted" /></template>
