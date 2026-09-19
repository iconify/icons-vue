<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrh4_jbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xrh4_jbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:music-note" /></template>
