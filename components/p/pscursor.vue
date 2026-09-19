<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scb29lb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="scb29lb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pscursor" /></template>
