<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m07vq1b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m07vq1b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mayan-edms-light" /></template>
