<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy2sqfbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy2sqfbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qrcode-2-fill" /></template>
