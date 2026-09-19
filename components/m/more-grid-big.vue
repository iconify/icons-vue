<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu17pzbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu17pzbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:more-grid-big" /></template>
