<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5sm3i20k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="j5sm3i20k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-right-fill" /></template>
