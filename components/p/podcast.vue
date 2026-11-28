<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5yb7_bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5yb7_bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:podcast" /></template>
