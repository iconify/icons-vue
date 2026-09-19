<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0dqwhbgb.css';
import '../../css/j/jzyuqzbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0dqwhbgb"/><path class="jzyuqzbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-woman" /></template>
