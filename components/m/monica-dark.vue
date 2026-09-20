<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hve1lylaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hve1lylaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:monica-dark" /></template>
