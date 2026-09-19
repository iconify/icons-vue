<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnw4xmazt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nnw4xmazt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:med" /></template>
