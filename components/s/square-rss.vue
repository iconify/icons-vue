<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7eqbg9te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l7eqbg9te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:square-rss" /></template>
