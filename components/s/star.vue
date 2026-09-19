<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvxfi23oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yvxfi23oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:star" /></template>
