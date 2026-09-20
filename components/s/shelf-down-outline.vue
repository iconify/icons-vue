<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9x59-bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e9x59-bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shelf-down-outline" /></template>
