<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d36krc8rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d36krc8rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pencil-fill" /></template>
