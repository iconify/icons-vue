<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji14zbbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ji14zbbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wheelie-bin-and-leaf" /></template>
