<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uatcl-bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uatcl-bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:round-arrow-6" /></template>
