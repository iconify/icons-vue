<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ybsn588zh.css';
import '../../css/u/uv9aobclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ybsn588zh"/><path class="uv9aobclp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-plus-round" /></template>
