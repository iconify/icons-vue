<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5df1egve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v5df1egve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:speech-bubbles-rtl" /></template>
