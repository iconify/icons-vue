<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkz8u0d4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qkz8u0d4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-hole-light" /></template>
