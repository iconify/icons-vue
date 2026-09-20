<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxahw3b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxahw3b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:theme-filled" /></template>
