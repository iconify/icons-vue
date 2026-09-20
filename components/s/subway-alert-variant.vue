<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwm8xi_bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwm8xi_bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:subway-alert-variant" /></template>
