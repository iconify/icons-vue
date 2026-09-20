<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blzm3ki0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blzm3ki0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orca-slicer-dark" /></template>
