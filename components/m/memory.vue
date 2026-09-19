<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bacfu3bgr.css';
import '../../css/z/zhfv58bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bacfu3bgr"/><path class="zhfv58bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:memory" /></template>
