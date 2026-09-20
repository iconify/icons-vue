<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq7w1ubzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dq7w1ubzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:puzzle-piece-16" /></template>
