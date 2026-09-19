<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grb34gbeb.css';
import '../../css/m/mlcrs6b_l.css';
import '../../css/n/ne1pfgevp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="grb34gbeb"/><path class="mlcrs6b_l"/><path class="ne1pfgevp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:racket" /></template>
