<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0e-0_k2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0e-0_k2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:route" /></template>
