<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzj-a2bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzj-a2bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spell-book" /></template>
