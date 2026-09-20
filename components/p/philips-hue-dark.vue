<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftd6m5bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftd6m5bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:philips-hue-dark" /></template>
