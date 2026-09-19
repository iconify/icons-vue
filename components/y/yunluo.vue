<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6h9g5kbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6h9g5kbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:yunluo" /></template>
