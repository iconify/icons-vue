<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd0m-8bdh.css';
import '../../css/u/uc8haducx.css';
import '../../css/e/e01ksbcky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="zd0m-8bdh"><path class="uc8haducx"/><path class="e01ksbcky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:thesvg-dark" /></template>
