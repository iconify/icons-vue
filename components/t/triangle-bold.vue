<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvxu01krm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pvxu01krm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:triangle-bold" /></template>
