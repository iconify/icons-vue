<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1nyiyxfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1nyiyxfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sofi-dark" /></template>
