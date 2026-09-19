<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cef4ribmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="cef4ribmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:window-restore" /></template>
