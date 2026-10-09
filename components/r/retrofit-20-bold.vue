<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmgp-hp4m.css';
import '../../css/p/pp2z-qb2n.css';
import '../../css/d/dp7t9qbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="pp2z-qb2n"/><path class="dp7t9qbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:retrofit-20-bold" /></template>
