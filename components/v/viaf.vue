<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f89z9b01p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f89z9b01p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:viaf" /></template>
