<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5usb4bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5usb4bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:swap-duotone" /></template>
