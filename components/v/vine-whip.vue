<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjblog4ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjblog4ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vine-whip" /></template>
