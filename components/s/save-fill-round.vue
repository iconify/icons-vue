<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nley873cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nley873cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-fill-round" /></template>
