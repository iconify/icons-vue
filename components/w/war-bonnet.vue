<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyrm0abvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyrm0abvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:war-bonnet" /></template>
