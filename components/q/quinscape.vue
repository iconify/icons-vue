<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npv1kvbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npv1kvbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:quinscape" /></template>
