<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ourbmvnkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ourbmvnkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:share" /></template>
