<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-qr39bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-qr39bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:page-layout-marginals" /></template>
