<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m20auyf3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":472};
const content = `<path class="m20auyf3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:rss-icon" /></template>
