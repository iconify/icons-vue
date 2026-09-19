<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng3z04b6k.css';
import '../../css/l/l2gxg7bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ng3z04b6k"/><path class="l2gxg7bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-time" /></template>
