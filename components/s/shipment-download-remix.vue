<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3_uhc5qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w3_uhc5qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-download-remix" /></template>
