<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef8_ic69j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ef8_ic69j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picpeak" /></template>
