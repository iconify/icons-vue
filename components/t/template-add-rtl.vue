<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjz52tsns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tjz52tsns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:template-add-rtl" /></template>
