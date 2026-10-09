<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dny5eubpk.css';
import '../../css/l/l2cqzcbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dny5eubpk"/><path class="l2cqzcbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-lock-20-bold" /></template>
