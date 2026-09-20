<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwmsxflvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hwmsxflvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-upload-solid" /></template>
