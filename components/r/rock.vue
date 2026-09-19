<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggo69_jeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ggo69_jeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:rock" /></template>
