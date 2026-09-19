<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph_x37bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ph_x37bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:recycle" /></template>
