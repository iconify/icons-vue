<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3o57d_5v.css';
import '../../css/g/g_pbthpru.css';
import '../../css/v/vlpxa7bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3o57d_5v"/><path class="g_pbthpru"/><path class="vlpxa7bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-angle-20" /></template>
