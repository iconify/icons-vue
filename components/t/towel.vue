<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j--2r6bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j--2r6bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:towel" /></template>
