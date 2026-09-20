<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx1pxqcgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wx1pxqcgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:navigation-arrow-north-flat" /></template>
