<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4a-q3f0p.css';
import '../../css/h/hq809sb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b4a-q3f0p"/><path class="hq809sb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tag-20-bold" /></template>
