<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuil0dbas.css';
import '../../css/d/dzyouclrc.css';
import '../../css/c/cum2y9o2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zuil0dbas"/><path class="dzyouclrc"/><path class="cum2y9o2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:not-gate-20-bold" /></template>
