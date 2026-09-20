<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv-7bgz2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uv-7bgz2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-3-outline" /></template>
