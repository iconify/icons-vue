<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrp1dvb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yrp1dvb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tv" /></template>
