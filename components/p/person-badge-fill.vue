<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ku27byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d0ku27byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-badge-fill" /></template>
