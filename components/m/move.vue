<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_2witbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_2witbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:move" /></template>
