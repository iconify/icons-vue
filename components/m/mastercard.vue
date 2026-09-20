<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wez-d0bjf.css';
import '../../css/a/a3l3mwbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wez-d0bjf"/><path class="a3l3mwbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mastercard" /></template>
