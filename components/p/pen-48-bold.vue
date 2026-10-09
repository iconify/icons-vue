<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6_diewni.css';
import '../../css/y/yig4ixxde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6_diewni"/><path class="yig4ixxde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-48-bold" /></template>
