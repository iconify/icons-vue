<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6d3_fr3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6d3_fr3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rss-locked" /></template>
