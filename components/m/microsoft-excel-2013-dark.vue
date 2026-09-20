<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3s8cpblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3s8cpblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2013-dark" /></template>
