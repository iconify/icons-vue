<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnioaab0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="fnioaab0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:tornado" /></template>
