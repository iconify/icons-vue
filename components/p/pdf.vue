<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmwvc3b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wmwvc3b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:pdf" /></template>
