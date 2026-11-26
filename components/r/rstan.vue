<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8wktyb4m.css';
import '../../css/u/ug4rhybvc.css';
import '../../css/q/qb6du5bre.css';
import '../../css/k/k57yvjept.css';
import '../../css/w/wpdd3kusk.css';
import '../../css/u/u6wk6r2bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l8wktyb4m"/><path class="ug4rhybvc"/><path class="qb6du5bre"/><path class="k57yvjept"/><path class="wpdd3kusk"/><path class="u6wk6r2bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rstan" /></template>
