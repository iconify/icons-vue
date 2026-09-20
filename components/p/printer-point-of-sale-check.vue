<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8bybblsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8bybblsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-check" /></template>
