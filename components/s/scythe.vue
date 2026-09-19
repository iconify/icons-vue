<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu340b6zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bu340b6zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scythe" /></template>
