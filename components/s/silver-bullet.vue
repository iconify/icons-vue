<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvjuc8mso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pvjuc8mso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:silver-bullet" /></template>
