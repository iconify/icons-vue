<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9xxoy94z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a9xxoy94z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rss-48-bold" /></template>
