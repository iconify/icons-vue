<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiup55cbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aiup55cbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-check-remix" /></template>
