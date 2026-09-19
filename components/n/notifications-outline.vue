<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo4jgab5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eo4jgab5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:notifications-outline" /></template>
