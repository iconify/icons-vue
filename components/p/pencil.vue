<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u21m0sbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="u21m0sbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pencil" /></template>
