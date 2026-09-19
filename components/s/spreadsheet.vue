<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os3mvyh4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="os3mvyh4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:spreadsheet" /></template>
