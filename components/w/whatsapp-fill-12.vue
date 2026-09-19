<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxlz_6eqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mxlz_6eqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:whatsapp-fill-12" /></template>
