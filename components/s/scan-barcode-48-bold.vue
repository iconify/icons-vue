<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8cubpb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8cubpb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-barcode-48-bold" /></template>
