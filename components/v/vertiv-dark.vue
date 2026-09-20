<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iotd1qbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iotd1qbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vertiv-dark" /></template>
