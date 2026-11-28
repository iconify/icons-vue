<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpwr8lbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpwr8lbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:scan-search" /></template>
