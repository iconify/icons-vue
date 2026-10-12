<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42z9ru9b.css';
import '../../css/j/jwdu1gbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k42z9ru9b"/><path class="jwdu1gbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rabbit-20" /></template>
