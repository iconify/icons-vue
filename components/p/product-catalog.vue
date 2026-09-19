<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_j7oubaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s_j7oubaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:product-catalog" /></template>
