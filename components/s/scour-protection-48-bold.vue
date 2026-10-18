<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2jxlvb2i.css';
import '../../css/t/t-4rqjbfm.css';
import '../../css/k/ke-yukwch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2jxlvb2i"/><path class="t-4rqjbfm"/><path class="ke-yukwch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scour-protection-48-bold" /></template>
