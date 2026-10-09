<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh1gyn4rx.css';
import '../../css/d/dh_lsrzrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nh1gyn4rx"/><path class="dh_lsrzrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-card-20" /></template>
