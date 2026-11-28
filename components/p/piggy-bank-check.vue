<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp_kx_kzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp_kx_kzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:piggy-bank-check" /></template>
