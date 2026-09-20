<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxg5-fbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uxg5-fbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:pdf-reader-application" /></template>
