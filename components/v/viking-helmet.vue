<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdqml2b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdqml2b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:viking-helmet" /></template>
