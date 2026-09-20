<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iff-y2boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iff-y2boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:zoom-in-outline" /></template>
