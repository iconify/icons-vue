<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my6nuwbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="my6nuwbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-wordle-light" /></template>
