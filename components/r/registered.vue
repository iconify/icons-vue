<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyu5r4bdv.css';
import '../../css/g/guh-_zb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu5r4bdv"/><path class="guh-_zb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:registered" /></template>
