<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1dgdy9az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="t1dgdy9az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project" /></template>
