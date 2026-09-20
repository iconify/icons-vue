<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stxl60b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="stxl60b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:threat-usb-solid" /></template>
