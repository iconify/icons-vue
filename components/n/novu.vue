<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1wd-4xhl.css';
import '../../css/b/bkrbpbclo.css';
import '../../css/m/mtyemfz0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGeiluzbIR" x1="512" x2="0" y2="512" gradientUnits="userSpaceOnUse"><stop offset=".232" class="b1wd-4xhl"/><stop offset=".802" class="bkrbpbclo"/></linearGradient><path fill="url(#SVGeiluzbIR)" class="mtyemfz0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:novu" /></template>
