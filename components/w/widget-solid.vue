<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_2qp6bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="k_2qp6bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:widget-solid" /></template>
