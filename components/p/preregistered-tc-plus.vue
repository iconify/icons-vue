<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmnvom9vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmnvom9vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-tc-plus" /></template>
