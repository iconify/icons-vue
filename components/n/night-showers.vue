<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3luk2kpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="h3luk2kpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-showers" /></template>
