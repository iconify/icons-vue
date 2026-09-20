<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmo-e9byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="hmo-e9byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:milestone" /></template>
