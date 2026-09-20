<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc_3xnmin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vc_3xnmin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:markdownlint" /></template>
