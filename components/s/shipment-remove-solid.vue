<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc__70bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oc__70bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-remove-solid" /></template>
