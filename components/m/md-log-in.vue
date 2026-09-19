<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y17d--b1p.css';
import '../../css/u/u2-ilg5vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y17d--b1p"/><path class="u2-ilg5vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-log-in" /></template>
