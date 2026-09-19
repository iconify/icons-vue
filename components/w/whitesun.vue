<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bri926yrn.css';
import '../../css/b/b1qs3_bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bri926yrn"/><circle class="b1qs3_bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitesun" /></template>
