<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-l4qbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mo-l4qbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:rss" /></template>
