<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl1yt9bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl1yt9bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:music-note-solid-expressive" /></template>
