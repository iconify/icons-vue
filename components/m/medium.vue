<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu5ad5q4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu5ad5q4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:medium" /></template>
