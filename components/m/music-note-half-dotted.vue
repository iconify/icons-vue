<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhjc9obbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhjc9obbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-half-dotted" /></template>
