<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjrjh-9qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjrjh-9qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pen" /></template>
