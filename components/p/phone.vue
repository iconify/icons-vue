<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksn07eq4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ksn07eq4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone" /></template>
