<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq28njb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pq28njb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ox" /></template>
