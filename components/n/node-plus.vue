<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5s6u5btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5s6u5btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:node-plus" /></template>
