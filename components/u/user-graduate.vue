<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmfou0x8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wmfou0x8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-graduate" /></template>
