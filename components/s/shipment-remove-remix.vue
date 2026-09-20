<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvtm0sbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yvtm0sbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-remove-remix" /></template>
