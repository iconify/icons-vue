<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1acuibhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f1acuibhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-property" /></template>
