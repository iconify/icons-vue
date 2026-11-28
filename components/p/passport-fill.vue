<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqc70yb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jqc70yb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:passport-fill" /></template>
