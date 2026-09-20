<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg0wxebyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mg0wxebyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:suspension-railway" /></template>
