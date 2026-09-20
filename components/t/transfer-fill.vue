<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbjvtxb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbjvtxb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-fill" /></template>
