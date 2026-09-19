<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huc0kzbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="huc0kzbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:th-large" /></template>
