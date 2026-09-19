<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9c09xb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t9c09xb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:stopwatch" /></template>
