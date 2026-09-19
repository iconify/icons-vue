<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg9g2nw8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9g2nw8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:shop" /></template>
