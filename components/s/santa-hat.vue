<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6yzs0btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6yzs0btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:santa-hat" /></template>
