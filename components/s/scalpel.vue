<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9_8gbccn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n9_8gbccn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scalpel" /></template>
