<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q93mhbc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q93mhbc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scan-qr-code" /></template>
