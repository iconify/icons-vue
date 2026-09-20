<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk9j0tbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jk9j0tbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple-and-shekel" /></template>
