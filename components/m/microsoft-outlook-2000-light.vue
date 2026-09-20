<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omgu7_bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omgu7_bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2000-light" /></template>
