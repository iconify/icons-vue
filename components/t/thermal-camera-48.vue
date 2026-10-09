<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zncj9xbho.css';
import '../../css/j/j2czn_mgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zncj9xbho"/><path class="j2czn_mgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-camera-48" /></template>
