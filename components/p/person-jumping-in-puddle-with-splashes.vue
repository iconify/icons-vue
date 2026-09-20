<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-nu6kbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v-nu6kbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-jumping-in-puddle-with-splashes" /></template>
