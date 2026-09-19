<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umxo5vd2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="umxo5vd2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:question" /></template>
