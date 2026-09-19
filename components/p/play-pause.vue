<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9l4lebje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9l4lebje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:play-pause" /></template>
