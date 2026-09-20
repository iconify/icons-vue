<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5exk6e-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f5exk6e-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:veterinary-14" /></template>
