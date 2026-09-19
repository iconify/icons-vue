<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f57e4fxjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":482,"height":512};
const content = `<path class="f57e4fxjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:ussunnah" /></template>
