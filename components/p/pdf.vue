<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnnwnd5sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xnnwnd5sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pdf" /></template>
