<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu3u76b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fu3u76b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rotten-tomatoes-light" /></template>
