<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoki9_bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qoki9_bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:view-stream" /></template>
