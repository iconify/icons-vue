<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zihtko4od.css';
import '../../css/o/oalqs3ghm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zihtko4od"/><path class="oalqs3ghm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rocket-stroke-20" /></template>
