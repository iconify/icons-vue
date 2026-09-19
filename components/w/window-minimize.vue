<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgt78jbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="mgt78jbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:window-minimize" /></template>
