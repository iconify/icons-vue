<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rva42cbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rva42cbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:signpost-r-1" /></template>
