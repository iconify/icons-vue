<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4-haccyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="h4-haccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopify" /></template>
