<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-7q2l6ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":700,"left":-30,"top":-94};
const content = `<path class="g-7q2l6ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:snowpack" /></template>
