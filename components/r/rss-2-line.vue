<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-8d71q8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-8d71q8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rss-2-line" /></template>
