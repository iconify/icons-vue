<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk-_17g4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-_17g4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sitemap-plus" /></template>
