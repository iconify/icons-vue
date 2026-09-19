<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_jpu8fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl_jpu8fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wifi-signal-4" /></template>
