<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6bv4yrfa.css';
import '../../css/p/pkyc0qbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="u6bv4yrfa"/><path class="pkyc0qbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ruby" /></template>
