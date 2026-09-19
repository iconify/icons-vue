<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/caaopxbqh.css';
import '../../css/y/y0rijtbja.css';
import '../../css/k/kqva0-m9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="caaopxbqh"/><circle class="y0rijtbja"/><circle class="kqva0-m9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shopping-cart-two" /></template>
