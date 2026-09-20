<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rylovv_qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rylovv_qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-fast" /></template>
