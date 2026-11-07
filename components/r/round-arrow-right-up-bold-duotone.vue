<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/a/aqgeitbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="aqgeitbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-up-bold-duotone" /></template>
