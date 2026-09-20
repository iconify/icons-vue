<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgbim8_qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgbim8_qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:torch-off" /></template>
