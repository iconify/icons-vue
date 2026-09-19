<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcg2rnyti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jcg2rnyti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-spear" /></template>
