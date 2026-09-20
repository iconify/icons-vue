<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpf011s-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fpf011s-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-wall" /></template>
