<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh7t0lb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hh7t0lb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water" /></template>
