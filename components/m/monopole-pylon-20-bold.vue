<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9fsllkmh.css';
import '../../css/o/ocy9tacha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9fsllkmh"/><path class="ocy9tacha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopole-pylon-20-bold" /></template>
