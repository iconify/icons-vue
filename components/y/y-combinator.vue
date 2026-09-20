<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf73bwb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf73bwb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:y-combinator" /></template>
