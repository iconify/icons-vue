<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0cnkibtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0cnkibtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-sudoku-dark" /></template>
