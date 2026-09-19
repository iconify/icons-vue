<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgis7cprr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgis7cprr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:up-angle-arrow" /></template>
