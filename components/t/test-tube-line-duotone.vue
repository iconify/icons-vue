<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dsskz8slx.css';
import '../../css/u/uk6bxm1hn.css';
import '../../css/b/bfq4gdi_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dsskz8slx"/><path class="uk6bxm1hn"/><path class="bfq4gdi_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:test-tube-line-duotone" /></template>
