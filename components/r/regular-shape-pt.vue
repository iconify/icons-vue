<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8lam-buj.css';
import '../../css/c/cyt_a1kut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="s8lam-buj"/><path class="cyt_a1kut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:regular-shape-pt" /></template>
