<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr97qdbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fr97qdbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:readme" /></template>
