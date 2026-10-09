<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl6xnzcek.css';
import '../../css/u/u4btp48pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jl6xnzcek"/><path class="u4btp48pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refinery-20" /></template>
