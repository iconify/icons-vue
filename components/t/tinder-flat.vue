<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8-6i4bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n8-6i4bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:tinder-flat" /></template>
