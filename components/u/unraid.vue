<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6b8rw7da.css';
import '../../css/v/v6i8d8bmx.css';
import '../../css/j/jk3br8gfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGwAGUUFca" x1="91.05" x2="420.95" y1="698.55" y2="368.65" gradientTransform="translate(0 -277.8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m6b8rw7da"/><stop offset="1" class="v6i8d8bmx"/></linearGradient><path fill="url(#SVGwAGUUFca)" class="jk3br8gfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unraid" /></template>
