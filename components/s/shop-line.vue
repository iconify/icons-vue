<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy4jracrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy4jracrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shop-line" /></template>
