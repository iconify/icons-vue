<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td2ntbexb.css';
import '../../css/w/w74p6ub3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="td2ntbexb"/><path class="w74p6ub3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vertx" /></template>
