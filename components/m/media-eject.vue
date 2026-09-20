<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9pq_3bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9pq_3bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-eject" /></template>
