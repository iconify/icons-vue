<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjozgk1xh.css';
import '../../css/v/vfyr6kgzz.css';
import '../../css/w/w-aohegfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cjozgk1xh"/><path class="vfyr6kgzz"/><path class="w-aohegfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stadium-20-bold" /></template>
