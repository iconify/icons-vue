<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xskbo8bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xskbo8bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:signpost-duo-1" /></template>
