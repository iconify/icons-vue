<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubhg269_g.css';
import '../../css/h/hsrqj8b_j.css';
import '../../css/p/pt6rgpv5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubhg269_g"/><path class="hsrqj8b_j"/><path class="pt6rgpv5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underground-cable-20" /></template>
