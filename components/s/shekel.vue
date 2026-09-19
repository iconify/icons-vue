<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umo7ipbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="umo7ipbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:shekel" /></template>
