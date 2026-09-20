<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mep9_ebte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mep9_ebte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roku" /></template>
