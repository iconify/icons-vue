<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joapl9b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="joapl9b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:music-note" /></template>
