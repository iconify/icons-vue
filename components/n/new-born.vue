<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gelrdccjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gelrdccjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:new-born" /></template>
