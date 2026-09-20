<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzun-2b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzun-2b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-check-outline" /></template>
