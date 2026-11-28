<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7si68brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7si68brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rss-x" /></template>
