<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjl5j-b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjl5j-b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tentacles-skull" /></template>
