<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpiw1ijfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vpiw1ijfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:sun" /></template>
