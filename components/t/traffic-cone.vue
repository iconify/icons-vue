<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbqm8nb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jbqm8nb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:traffic-cone" /></template>
