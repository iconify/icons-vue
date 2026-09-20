<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqlim6brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqlim6brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-outline" /></template>
