<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdtpx_b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdtpx_b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-mold" /></template>
