<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5jvdcriy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5jvdcriy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zed-dark" /></template>
