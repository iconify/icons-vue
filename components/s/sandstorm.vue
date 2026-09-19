<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op49qozpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="op49qozpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sandstorm" /></template>
