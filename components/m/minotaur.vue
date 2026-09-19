<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7n1v6lug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7n1v6lug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:minotaur" /></template>
