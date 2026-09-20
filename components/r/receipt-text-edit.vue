<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iohu4wb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iohu4wb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-edit" /></template>
