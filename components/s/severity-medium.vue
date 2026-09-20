<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydsmyebdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ydsmyebdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:severity-medium" /></template>
