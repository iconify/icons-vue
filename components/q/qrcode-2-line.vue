<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdhd6-b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdhd6-b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qrcode-2-line" /></template>
