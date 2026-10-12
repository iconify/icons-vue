<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lehxztmwm.css';
import '../../css/r/r_0sobc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lehxztmwm"/><path class="r_0sobc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:protractor-20-bold" /></template>
