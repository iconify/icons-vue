<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bto_4-vps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bto_4-vps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thermometer" /></template>
