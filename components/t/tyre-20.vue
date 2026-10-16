<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3xaacjo.css';
import '../../css/l/l5cqi8bbb.css';
import '../../css/s/sz2puvbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="l5cqi8bbb"/><path class="sz2puvbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tyre-20" /></template>
