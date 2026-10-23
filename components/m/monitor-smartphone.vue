<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr7z0_bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr7z0_bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:monitor-smartphone" /></template>
