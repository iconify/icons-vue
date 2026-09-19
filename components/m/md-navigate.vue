<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4u8obcgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4u8obcgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-navigate" /></template>
