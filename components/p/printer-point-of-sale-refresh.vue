<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slxj0bb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slxj0bb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-refresh" /></template>
