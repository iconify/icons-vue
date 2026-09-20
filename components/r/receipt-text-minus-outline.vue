<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpul06c7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpul06c7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-minus-outline" /></template>
