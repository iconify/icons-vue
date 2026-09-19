<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilt682bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ilt682bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mango" /></template>
