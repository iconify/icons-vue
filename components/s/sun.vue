<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwu80rb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwu80rb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sun" /></template>
