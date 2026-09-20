<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tib1-l6ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tib1-l6ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:scan-barcode" /></template>
