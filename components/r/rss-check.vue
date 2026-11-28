<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s57qfya-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s57qfya-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rss-check" /></template>
