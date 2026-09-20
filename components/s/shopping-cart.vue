<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa8f_iukb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-4};
const content = `<path class="wa8f_iukb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shopping-cart" /></template>
