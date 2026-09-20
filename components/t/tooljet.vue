<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph0f_bbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ph0f_bbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tooljet" /></template>
