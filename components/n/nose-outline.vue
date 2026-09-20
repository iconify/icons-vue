<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cws1dcbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cws1dcbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nose-outline" /></template>
