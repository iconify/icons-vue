<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvl9v5b9e.css';
import '../../css/o/oqfk99ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yvl9v5b9e"/><path class="oqfk99ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-diamond" /></template>
