<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilrh5njzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilrh5njzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:scan-barcode-sharp" /></template>
