<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ricakl_nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ricakl_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:plane" /></template>
