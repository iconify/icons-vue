<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s64jidcwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s64jidcwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:valley" /></template>
