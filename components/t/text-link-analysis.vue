<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5zc53bhn.css';
import '../../css/o/otd0eoc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k5zc53bhn"/><path class="otd0eoc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-link-analysis" /></template>
