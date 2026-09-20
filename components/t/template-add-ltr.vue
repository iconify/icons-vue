<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moqj_8bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="moqj_8bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:template-add-ltr" /></template>
