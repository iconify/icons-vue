<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwy4c41lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwy4c41lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nanote-dark" /></template>
