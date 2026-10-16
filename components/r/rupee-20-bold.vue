<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt3s35byo.css';
import '../../css/u/uby7xibdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rt3s35byo"/><path class="uby7xibdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rupee-20-bold" /></template>
