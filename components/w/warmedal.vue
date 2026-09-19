<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwto_gbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="iwto_gbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:warmedal" /></template>
