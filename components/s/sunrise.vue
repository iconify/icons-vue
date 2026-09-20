<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi-w9dbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-w9dbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sunrise" /></template>
