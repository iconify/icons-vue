<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnukzj0as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wnukzj0as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sankeychart" /></template>
