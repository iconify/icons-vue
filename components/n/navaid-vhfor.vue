<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_ct5bjf.css';
import '../../css/e/es579g_1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vg_ct5bjf"/><path class="es579g_1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:navaid-vhfor" /></template>
