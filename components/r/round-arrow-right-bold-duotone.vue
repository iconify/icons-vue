<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/g/g2uxot4xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="g2uxot4xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-bold-duotone" /></template>
