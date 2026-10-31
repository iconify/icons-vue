<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp4c5_b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp4c5_b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-fill-round" /></template>
