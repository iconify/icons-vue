<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8x9wd4ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8x9wd4ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:meilisearch" /></template>
