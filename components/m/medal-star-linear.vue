<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v7q1lwidl.css';
import '../../css/v/ve0hig3pz.css';
import '../../css/y/y4qe-ubzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v7q1lwidl"/><path class="ve0hig3pz"/><path class="y4qe-ubzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-linear" /></template>
