<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8f9qnbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i8f9qnbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-template-16" /></template>
