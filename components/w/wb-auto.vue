<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj2ys662g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="vj2ys662g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wb-auto" /></template>
