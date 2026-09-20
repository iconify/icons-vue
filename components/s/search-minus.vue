<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-lvolbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="r-lvolbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:search-minus" /></template>
