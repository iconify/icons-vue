<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru669i_fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru669i_fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meme-search-light" /></template>
