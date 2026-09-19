<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kda-sptxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="kda-sptxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake-1" /></template>
