<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceex6qbaz.css';
import '../../css/c/chgc5thhd.css';
import '../../css/h/hyns0sb6c.css';
import '../../css/d/ds_4hp33i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ceex6qbaz"/><path class="chgc5thhd"/><path class="hyns0sb6c"/><path class="ds_4hp33i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-canopy-20" /></template>
