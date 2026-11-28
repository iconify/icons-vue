<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrme9n-sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jrme9n-sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:stack-simple-check" /></template>
