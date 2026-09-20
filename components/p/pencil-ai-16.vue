<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnmef8g9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pnmef8g9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pencil-ai-16" /></template>
