<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab48hf36a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ab48hf36a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-21-the-world" /></template>
