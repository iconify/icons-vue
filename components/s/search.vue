<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfj2ffzpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfj2ffzpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:search" /></template>
