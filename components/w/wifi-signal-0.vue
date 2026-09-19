<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_8bgru1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_8bgru1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wifi-signal-0" /></template>
