<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp92r26xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hp92r26xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:quidditch-broom-ball" /></template>
