<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f73y469bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f73y469bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:movie" /></template>
