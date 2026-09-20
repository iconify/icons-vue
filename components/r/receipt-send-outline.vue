<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjxy9soza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjxy9soza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-send-outline" /></template>
