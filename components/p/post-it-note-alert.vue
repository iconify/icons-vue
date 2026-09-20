<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y06qdmsvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y06qdmsvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-note-alert" /></template>
