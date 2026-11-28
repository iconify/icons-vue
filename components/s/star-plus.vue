<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez9hryb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez9hryb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:star-plus" /></template>
