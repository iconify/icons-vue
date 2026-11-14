<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cc0yg-bhd.css';
import '../../css/j/jy51gjgdv.css';
import '../../css/l/ly3xvooyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cc0yg-bhd"/><path class="jy51gjgdv"/><path class="ly3xvooyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:settings-error-01" /></template>
