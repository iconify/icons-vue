<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt7tz5iod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dt7tz5iod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-outline" /></template>
