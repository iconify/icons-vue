<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s833exkju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s833exkju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:mendeley-square" /></template>
