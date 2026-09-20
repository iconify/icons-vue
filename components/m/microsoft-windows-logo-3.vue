<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbd3abb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbd3abb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-windows-logo-3" /></template>
