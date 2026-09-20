<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8113pt6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d8113pt6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-add-column-before-rtl" /></template>
