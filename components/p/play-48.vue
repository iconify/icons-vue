<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgeo2czcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wgeo2czcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:play-48" /></template>
