<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4-l-qb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u4-l-qb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:truck-loading-solid" /></template>
