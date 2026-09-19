<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc3ewx6xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jc3ewx6xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mining" /></template>
