<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqae7zbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqae7zbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-globe" /></template>
