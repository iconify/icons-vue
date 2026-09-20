<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi_htnp5m.css';
import '../../css/b/bvztumbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_htnp5m"/><ellipse class="bvztumbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tether-usdt-line" /></template>
