<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js1dubcgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js1dubcgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-arrow-right-outline" /></template>
