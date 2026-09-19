<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p84lp4bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p84lp4bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:map-signs" /></template>
