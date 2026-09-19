<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3308_fmz.css';
import '../../css/e/e2itionyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3308_fmz"/><path class="e2itionyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scan-barcode-filled" /></template>
