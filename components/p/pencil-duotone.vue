<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zlhl_01ib.css';
import '../../css/r/rx626mzkf.css';
import '../../css/u/uyhdqmb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zlhl_01ib"/><path class="rx626mzkf"/><path class="uyhdqmb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pencil-duotone" /></template>
