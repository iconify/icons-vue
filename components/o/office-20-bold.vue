<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_1_eqb9t.css';
import '../../css/q/q02p0rb4d.css';
import '../../css/f/fwy8obcmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n_1_eqb9t"/><path class="q02p0rb4d"/><path class="fwy8obcmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:office-20-bold" /></template>
