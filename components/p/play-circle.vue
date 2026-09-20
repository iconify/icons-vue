<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxzq55xig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fxzq55xig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:play-circle" /></template>
