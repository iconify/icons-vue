<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuac8wbht.css';
import '../../css/a/a1eqfi1lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yuac8wbht"/><path class="a1eqfi1lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-lantern-20-bold" /></template>
