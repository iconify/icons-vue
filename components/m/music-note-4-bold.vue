<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1hccg7-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1hccg7-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-4-bold" /></template>
