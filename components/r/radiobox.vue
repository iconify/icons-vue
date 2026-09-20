<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw55usblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="aw55usblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:radiobox" /></template>
