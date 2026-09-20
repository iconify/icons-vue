<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_t59960j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_t59960j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-calendar-light" /></template>
