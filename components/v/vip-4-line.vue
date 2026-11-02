<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zszwr2big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zszwr2big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-4-line" /></template>
