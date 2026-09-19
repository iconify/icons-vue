<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldh1uqbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ldh1uqbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-tracking" /></template>
