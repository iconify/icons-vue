<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu2vrfbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mu2vrfbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:moac" /></template>
