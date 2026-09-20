<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f904tq0ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f904tq0ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:smiling-face" /></template>
