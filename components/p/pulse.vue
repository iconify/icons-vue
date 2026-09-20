<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2inalyzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w2inalyzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:pulse" /></template>
