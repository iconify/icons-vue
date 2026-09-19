<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlhhcj4sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vlhhcj4sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:triangle-half" /></template>
