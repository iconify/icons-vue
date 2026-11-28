<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5-b18bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5-b18bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:music-note-heart" /></template>
