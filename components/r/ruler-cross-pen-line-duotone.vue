<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/olhjwfbxv.css';
import '../../css/h/ht6vrl9xs.css';
import '../../css/p/ph4irppsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="olhjwfbxv"/><path class="ht6vrl9xs"/><path class="ph4irppsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-cross-pen-line-duotone" /></template>
