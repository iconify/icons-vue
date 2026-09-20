<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-dxvgbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-dxvgbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:tape" /></template>
