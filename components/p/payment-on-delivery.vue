<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln6t6pbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln6t6pbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:payment-on-delivery" /></template>
