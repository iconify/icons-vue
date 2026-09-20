<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq0_znbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oq0_znbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:truenas-core-dark" /></template>
