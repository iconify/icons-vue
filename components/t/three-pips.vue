<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fite9bvmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fite9bvmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-pips" /></template>
