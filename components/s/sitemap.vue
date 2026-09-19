<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh3v0bb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nh3v0bb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sitemap" /></template>
