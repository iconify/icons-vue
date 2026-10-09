<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4kx72bov.css';
import '../../css/n/n-zjmmulx.css';
import '../../css/q/q4l9ctu0n.css';
import '../../css/u/uq78lkwmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4kx72bov"/><path class="n-zjmmulx"/><path class="q4l9ctu0n"/><path class="uq78lkwmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vacuum-48-bold" /></template>
