<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6p0xmpux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p6p0xmpux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:signature-rtl" /></template>
