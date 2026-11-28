<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohpdf_bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohpdf_bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:signal" /></template>
