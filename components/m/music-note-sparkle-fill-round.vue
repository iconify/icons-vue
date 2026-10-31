<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6q8pkbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6q8pkbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-sparkle-fill-round" /></template>
