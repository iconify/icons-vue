<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujd6pxb0p.css';
import '../../css/k/k35tmdb5w.css';
import '../../css/k/k4leaeb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujd6pxb0p"/><path class="k35tmdb5w"/><path class="k4leaeb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-box-light" /></template>
