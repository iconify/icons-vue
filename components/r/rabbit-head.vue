<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqb96mbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqb96mbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rabbit-head" /></template>
