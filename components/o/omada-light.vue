<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvuee1bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvuee1bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omada-light" /></template>
