<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jizr6bbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jizr6bbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-download-solid" /></template>
