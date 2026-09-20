<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl3lnyh2h.css';
import '../../css/q/q3rs99g9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jl3lnyh2h"/><path class="q3rs99g9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-diamond" /></template>
