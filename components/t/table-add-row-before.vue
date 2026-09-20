<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy-485wlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hy-485wlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-add-row-before" /></template>
