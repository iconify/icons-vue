<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_9c2bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_9c2bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vinyl" /></template>
