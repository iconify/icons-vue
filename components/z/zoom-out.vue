<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1zwrqbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w1zwrqbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:zoom-out" /></template>
