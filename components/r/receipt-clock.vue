<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4k0wyb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4k0wyb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:receipt-clock" /></template>
