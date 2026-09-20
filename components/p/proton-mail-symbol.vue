<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy-6gvnnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-6gvnnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:proton-mail-symbol" /></template>
