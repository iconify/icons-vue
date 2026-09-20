<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy77tqblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iy77tqblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:nimblr" /></template>
