<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y66tzyk9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y66tzyk9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:qr-code-scan-1" /></template>
