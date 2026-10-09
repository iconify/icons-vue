<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpj3_ybqz.css';
import '../../css/w/wec04pbcz.css';
import '../../css/o/ota_86bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kpj3_ybqz"/><path class="wec04pbcz"/><path class="ota_86bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-direction-20-bold" /></template>
