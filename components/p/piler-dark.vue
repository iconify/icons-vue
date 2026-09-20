<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vip7vacjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vip7vacjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piler-dark" /></template>
