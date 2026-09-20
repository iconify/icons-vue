<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rylg1bu5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rylg1bu5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vinted" /></template>
