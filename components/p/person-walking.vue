<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4u8pbwjc.css';
import '../../css/b/b7k4vkb4y.css';
import '../../css/g/gcw1jebsm.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/k/kki4zxl5e.css';
import '../../css/u/ujseujbsm.css';
import '../../css/a/a847upcpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="x4u8pbwjc"><path class="b7k4vkb4y"/><circle class="gcw1jebsm"/></g><g class="x8poo_bjf"><ellipse class="kki4zxl5e"/><path class="ujseujbsm"/><path class="a847upcpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-walking" /></template>
