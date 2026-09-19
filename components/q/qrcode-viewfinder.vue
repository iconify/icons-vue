<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3bss3zbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d3bss3zbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:qrcode-viewfinder" /></template>
