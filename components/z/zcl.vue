<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dte3pvb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dte3pvb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zcl" /></template>
