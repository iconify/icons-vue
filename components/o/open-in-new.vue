<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw_57bbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="dw_57bbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:open-in-new" /></template>
