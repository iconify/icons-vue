<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb6pms4ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mb6pms4ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:puzzle-rtl" /></template>
