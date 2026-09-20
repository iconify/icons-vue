<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovp1n-bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ovp1n-bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:netwark" /></template>
