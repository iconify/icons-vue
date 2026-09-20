<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cscv_fw-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cscv_fw-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:system76" /></template>
