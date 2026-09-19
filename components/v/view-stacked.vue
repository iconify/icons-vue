<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cexna4b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cexna4b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:view-stacked" /></template>
