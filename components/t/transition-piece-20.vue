<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgu7rtifi.css';
import '../../css/z/zo-uulbpt.css';
import '../../css/b/b_y3iwjuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rgu7rtifi"/><path class="zo-uulbpt"/><path class="b_y3iwjuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transition-piece-20" /></template>
