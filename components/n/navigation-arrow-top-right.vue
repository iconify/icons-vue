<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5o3pmfii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i5o3pmfii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:navigation-arrow-top-right" /></template>
