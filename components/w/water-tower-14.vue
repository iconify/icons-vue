<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjo-3lbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zjo-3lbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:water-tower-14" /></template>
