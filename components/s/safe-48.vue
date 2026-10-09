<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwbw3abxb.css';
import '../../css/c/c7rkzybvo.css';
import '../../css/h/hberpve6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwbw3abxb"/><path class="c7rkzybvo"/><path class="hberpve6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safe-48" /></template>
