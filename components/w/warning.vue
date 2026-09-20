<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp8r-nmbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vp8r-nmbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning" /></template>
