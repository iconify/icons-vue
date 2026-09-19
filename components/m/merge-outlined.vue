<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mbtde-eiv.css';
import '../../css/h/hyrwp_buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g class="n1lsf0bnc"><path class="mbtde-eiv"/><path class="hyrwp_buz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:merge-outlined" /></template>
