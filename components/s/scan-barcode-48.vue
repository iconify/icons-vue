<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_sm0bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gn_sm0bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-barcode-48" /></template>
