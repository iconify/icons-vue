<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju6x--box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ju6x--box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:portal" /></template>
