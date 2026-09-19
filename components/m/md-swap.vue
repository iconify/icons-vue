<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msvckcy5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="msvckcy5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-swap" /></template>
