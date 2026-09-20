<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kem-rcb_x.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVG9pcnZPUV" class="kem-rcb_x"/></defs><use href="#SVG9pcnZPUV" transform="translate(42.667 53.333)" class="d2kvgvbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pen-filled" /></template>
