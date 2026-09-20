<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tllzjacdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tllzjacdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-receipt-cog-outline" /></template>
