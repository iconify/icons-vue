<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr-_q9brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="qr-_q9brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:menu-hamburger" /></template>
