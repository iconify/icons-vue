<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h92e2tbsy.css';
import '../../css/i/i_nsi3ucm.css';
import '../../css/p/p4-i55byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h92e2tbsy"/><path class="i_nsi3ucm"/><path class="p4-i55byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-stove-20-bold" /></template>
