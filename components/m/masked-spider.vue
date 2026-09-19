<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn3h6pbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nn3h6pbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:masked-spider" /></template>
