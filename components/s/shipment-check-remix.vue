<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz51hibla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz51hibla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shipment-check-remix" /></template>
