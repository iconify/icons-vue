<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_-74wdkk.css';
import '../../css/a/a5lgi4lwe.css';
import '../../css/t/t15dg5mzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g_-74wdkk"/><path class="a5lgi4lwe"/><path class="t15dg5mzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safe-20-bold" /></template>
