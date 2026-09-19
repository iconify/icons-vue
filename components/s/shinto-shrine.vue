<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puiv42zjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puiv42zjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shinto-shrine" /></template>
