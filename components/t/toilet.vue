<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp9j1o_0y.css';
import '../../css/u/uf_f1g_xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tp9j1o_0y"/><path class="uf_f1g_xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:toilet" /></template>
