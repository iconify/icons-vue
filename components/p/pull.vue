<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jri0kqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jri0kqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pull" /></template>
