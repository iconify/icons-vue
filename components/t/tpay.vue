<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-lvidefn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e-lvidefn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:tpay" /></template>
