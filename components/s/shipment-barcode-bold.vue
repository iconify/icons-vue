<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmwr6rb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmwr6rb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipment-barcode-bold" /></template>
