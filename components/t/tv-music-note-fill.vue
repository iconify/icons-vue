<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7i1p681y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d7i1p681y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tv-music-note-fill" /></template>
