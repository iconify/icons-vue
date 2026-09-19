<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmgs3-w5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmgs3-w5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:receipt-refund" /></template>
