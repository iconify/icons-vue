<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrv9ke-ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrv9ke-ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:presentation-solid" /></template>
