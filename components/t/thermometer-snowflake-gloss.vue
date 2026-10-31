<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my9lfcb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my9lfcb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thermometer-snowflake-gloss" /></template>
