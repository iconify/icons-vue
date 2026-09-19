<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7_8i1o_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="l7_8i1o_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:star-border" /></template>
