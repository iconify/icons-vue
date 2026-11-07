<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iim6b23_i.css';
import '../../css/z/zb2kedx8a.css';
import '../../css/h/h7hbobcdx.css';
import '../../css/u/ubfykzbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iim6b23_i"/><path class="zb2kedx8a"/><path class="h7hbobcdx"/><path class="ubfykzbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-circle-line-duotone" /></template>
