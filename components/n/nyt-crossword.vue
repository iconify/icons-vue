<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6gcwac9u.css';
import '../../css/c/czq6lnb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6gcwac9u"/><path class="czq6lnb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-crossword" /></template>
