<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3_17eb5m.css';
import '../../css/n/nknwp425q.css';
import '../../css/b/bzswhqb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w3_17eb5m"/><path class="nknwp425q"/><path class="bzswhqb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:winter-warning" /></template>
