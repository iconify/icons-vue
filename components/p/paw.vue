<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ron99bb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ron99bb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paw" /></template>
