<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th81w-wav.css';
import '../../css/w/wvtn6fmsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="th81w-wav"/><path class="wvtn6fmsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opengist" /></template>
