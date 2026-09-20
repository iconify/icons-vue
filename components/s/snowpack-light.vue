<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etyfe9bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":700,"left":-30,"top":-94};
const content = `<path class="etyfe9bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:snowpack-light" /></template>
