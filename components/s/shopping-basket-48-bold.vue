<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsiiptbtu.css';
import '../../css/d/dm-cxkseg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qsiiptbtu"/><path class="dm-cxkseg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shopping-basket-48-bold" /></template>
