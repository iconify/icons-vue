<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpmj4zicj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpmj4zicj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-sixteenth-dotted" /></template>
