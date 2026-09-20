<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frr319p9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frr319p9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nano" /></template>
