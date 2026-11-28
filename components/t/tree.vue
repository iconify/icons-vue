<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8b0dutxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8b0dutxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tree" /></template>
