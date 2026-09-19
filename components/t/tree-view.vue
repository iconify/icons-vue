<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifcugn6hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ifcugn6hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tree-view" /></template>
