<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo2pqcc3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo2pqcc3v"><animateTransform attributeName="transform" attributeType="XML" dur="10s" from="0 12 12" repeatCount="indefinite" to="360 12 12" type="rotate"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:rotating-gear" /></template>
