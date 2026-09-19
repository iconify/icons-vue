<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbecybbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fbecybbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tent-arrow-turn-left" /></template>
