<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj7_ltb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wj7_ltb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-mini-crossword-light" /></template>
