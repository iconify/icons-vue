<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3mg6mryn.css';
import '../../css/z/zykw2fvhd.css';
import '../../css/o/o1sgq7a6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y3mg6mryn"/><path class="zykw2fvhd"/><path class="o1sgq7a6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pumped-hydro-20" /></template>
