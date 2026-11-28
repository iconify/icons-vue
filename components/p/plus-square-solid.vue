<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxalj7bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxalj7bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plus-square-solid" /></template>
