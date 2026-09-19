<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abbymobak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abbymobak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:soonwithrightarrow" /></template>
