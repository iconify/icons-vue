<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0225_9gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0225_9gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ruby" /></template>
