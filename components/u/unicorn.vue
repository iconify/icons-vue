<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymho3rbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymho3rbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:unicorn" /></template>
