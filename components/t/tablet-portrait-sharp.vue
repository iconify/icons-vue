<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_8tfcbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_8tfcbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tablet-portrait-sharp" /></template>
