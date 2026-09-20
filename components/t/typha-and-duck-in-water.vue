<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-55etb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u-55etb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:typha-and-duck-in-water" /></template>
