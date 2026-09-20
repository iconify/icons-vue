<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f40os-3wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f40os-3wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pin-pad-with-shekel" /></template>
