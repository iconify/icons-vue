<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb5navbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sb5navbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:move-layer-up" /></template>
