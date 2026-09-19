<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlmcppvox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tlmcppvox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:txt-reference" /></template>
