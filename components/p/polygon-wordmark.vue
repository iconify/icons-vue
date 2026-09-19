<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-o-n6vfd.css';
import '../../css/h/hq6p7itxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a-o-n6vfd"/><path class="hq6p7itxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:polygon-wordmark" /></template>
