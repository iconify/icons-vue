<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf446b7gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wf446b7gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:scoop-of-ice-cream-in-cup" /></template>
