<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odhx_f5ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odhx_f5ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:piechart-ai" /></template>
