<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwl-lb6rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hwl-lb6rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-barcode-20-bold" /></template>
