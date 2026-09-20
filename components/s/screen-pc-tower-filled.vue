<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3wdnwb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h3wdnwb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-pc-tower-filled" /></template>
