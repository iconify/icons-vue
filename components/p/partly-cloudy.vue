<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo3l2xb1x.css';
import '../../css/m/mdqwd7bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uo3l2xb1x"/><path class="mdqwd7bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:partly-cloudy" /></template>
