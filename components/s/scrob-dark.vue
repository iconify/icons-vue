<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfedm6bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfedm6bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrob-dark" /></template>
