<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk-ptcqav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jk-ptcqav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmocompiler-light" /></template>
