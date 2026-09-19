<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu47qlb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vu47qlb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subflow-local" /></template>
