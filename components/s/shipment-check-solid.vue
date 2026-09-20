<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1-xhv5xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1-xhv5xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shipment-check-solid" /></template>
