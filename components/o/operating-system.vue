<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1j10obcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1j10obcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:operating-system" /></template>
