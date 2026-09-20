<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6a69czjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c6a69czjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:virtual" /></template>
