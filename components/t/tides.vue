<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boazfbb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="boazfbb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tides" /></template>
