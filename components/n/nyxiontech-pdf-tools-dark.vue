<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3m0nhb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3m0nhb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyxiontech-pdf-tools-dark" /></template>
