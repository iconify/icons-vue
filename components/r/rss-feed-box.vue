<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3d7mnbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3d7mnbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rss-feed-box" /></template>
