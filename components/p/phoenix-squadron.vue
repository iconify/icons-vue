<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou9vwqqhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ou9vwqqhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:phoenix-squadron" /></template>
