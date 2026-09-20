<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dar1jw_ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dar1jw_ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:michigan-with-capital-star" /></template>
