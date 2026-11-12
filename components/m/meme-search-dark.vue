<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrtps0hmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrtps0hmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meme-search-dark" /></template>
