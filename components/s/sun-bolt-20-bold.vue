<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/punxieblh.css';
import '../../css/z/zi252sbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="punxieblh"/><path class="zi252sbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-bolt-20-bold" /></template>
