<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baiiv2vew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="baiiv2vew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:prompt" /></template>
