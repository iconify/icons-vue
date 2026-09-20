<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir6en1bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ir6en1bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tools-16" /></template>
