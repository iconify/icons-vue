<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2re4u90q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2re4u90q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:palette" /></template>
