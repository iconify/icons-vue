<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re446-bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="re446-bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:worklenz-dark" /></template>
