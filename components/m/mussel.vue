<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebnm_jb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebnm_jb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mussel" /></template>
