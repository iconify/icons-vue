<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af_m9lb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="af_m9lb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-crossword-dark" /></template>
