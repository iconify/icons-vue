<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzjpt7h1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mzjpt7h1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:survey-point" /></template>
