<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygnhg0zau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygnhg0zau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sound-wave" /></template>
