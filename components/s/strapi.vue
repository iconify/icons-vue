<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yspcpzb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yspcpzb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:strapi" /></template>
