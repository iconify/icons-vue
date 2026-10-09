<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0i2p1bpi.css';
import '../../css/y/y0hffi4py.css';
import '../../css/z/zafs9vb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n0i2p1bpi"/><path class="y0hffi4py"/><path class="zafs9vb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milk-carton-20-bold" /></template>
