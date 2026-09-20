<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1tb8xbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="y1tb8xbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:range" /></template>
