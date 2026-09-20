<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8y_vccxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h8y_vccxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:update-rtl" /></template>
