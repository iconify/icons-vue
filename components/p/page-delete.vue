<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrkfhlbrj.css';
import '../../css/c/c0pcv8b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jrkfhlbrj"/><path class="c0pcv8b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-delete" /></template>
