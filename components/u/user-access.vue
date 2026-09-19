<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw06c_omj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yw06c_omj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-access" /></template>
