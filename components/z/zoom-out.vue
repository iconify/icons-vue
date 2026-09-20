<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj2_pbcuj.css';
import '../../css/s/sl3an4zge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="oj2_pbcuj"/><path class="sl3an4zge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:zoom-out" /></template>
