<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e81d7qbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e81d7qbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple-and-rupee" /></template>
