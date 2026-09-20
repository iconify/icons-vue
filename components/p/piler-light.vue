<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntw2ccbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntw2ccbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piler-light" /></template>
