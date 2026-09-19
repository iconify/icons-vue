<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec43qpnlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec43qpnlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicatorc" /></template>
