<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wff3039xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":456};
const content = `<path class="wff3039xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:radio" /></template>
