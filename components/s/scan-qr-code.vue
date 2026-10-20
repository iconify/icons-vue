<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smgj5gbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smgj5gbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scan-qr-code" /></template>
