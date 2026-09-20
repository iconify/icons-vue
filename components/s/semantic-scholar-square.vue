<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sihm51ipd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sihm51ipd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:semantic-scholar-square" /></template>
