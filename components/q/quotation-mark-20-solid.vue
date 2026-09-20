<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2hf5ceba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g2hf5ceba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:quotation-mark-20-solid" /></template>
