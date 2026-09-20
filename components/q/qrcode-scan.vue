<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffogr3zwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffogr3zwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:qrcode-scan" /></template>
