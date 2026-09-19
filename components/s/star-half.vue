<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2do9dblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2do9dblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:star-half" /></template>
