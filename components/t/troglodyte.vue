<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ork74pgmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ork74pgmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:troglodyte" /></template>
