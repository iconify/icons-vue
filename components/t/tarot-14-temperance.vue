<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0_00t29z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0_00t29z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-14-temperance" /></template>
