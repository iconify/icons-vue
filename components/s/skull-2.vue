<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fits8bbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fits8bbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:skull-2" /></template>
