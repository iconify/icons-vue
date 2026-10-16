<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yakfv4bol.css';
import '../../css/i/ivpk4lbsu.css';
import '../../css/h/hqe77eb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yakfv4bol"/><path class="ivpk4lbsu"/><path class="hqe77eb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-hydro-20" /></template>
