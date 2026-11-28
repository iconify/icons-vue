<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf9p40zkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf9p40zkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:suitcase" /></template>
