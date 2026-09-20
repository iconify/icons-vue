<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p-qrmibls.css';
import '../../css/i/i6nrt8nnu.css';
import '../../css/e/ey97octmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p-qrmibls"/><path class="i6nrt8nnu"/><path class="ey97octmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbon-star-line-duotone" /></template>
