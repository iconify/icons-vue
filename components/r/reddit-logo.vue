<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdwt9o_ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdwt9o_ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:reddit-logo" /></template>
