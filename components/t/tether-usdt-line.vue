<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzk1kzome.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzk1kzome"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tether-usdt-line" /></template>
