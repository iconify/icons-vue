<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw0hcjblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jw0hcjblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-sattelites" /></template>
