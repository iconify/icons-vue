<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_yuh5o2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g_yuh5o2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:price-tag" /></template>
