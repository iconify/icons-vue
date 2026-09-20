<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6-j_ctmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e6-j_ctmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:node-js" /></template>
