<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsf58_ncg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsf58_ncg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:search" /></template>
