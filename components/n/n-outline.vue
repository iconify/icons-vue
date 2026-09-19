<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2ofdew1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l2ofdew1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:n-outline" /></template>
