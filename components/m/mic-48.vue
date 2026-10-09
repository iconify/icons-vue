<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8sj0bbsc.css';
import '../../css/c/c75q7gbnf.css';
import '../../css/e/ezx2ctbsk.css';
import '../../css/z/z6thc6b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i8sj0bbsc"/><path class="c75q7gbnf"/><path class="ezx2ctbsk"/><path class="z6thc6b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mic-48" /></template>
