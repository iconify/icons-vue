<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w772vtf7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w772vtf7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:miota" /></template>
