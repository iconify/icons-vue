<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik2nfl_cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik2nfl_cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:packt" /></template>
