<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mym01l9ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mym01l9ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qrcode-fill" /></template>
