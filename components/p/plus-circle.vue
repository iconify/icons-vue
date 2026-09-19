<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7ex6tb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="n7ex6tb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:plus-circle" /></template>
