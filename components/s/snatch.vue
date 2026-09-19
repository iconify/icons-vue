<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp5eyfboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lp5eyfboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snatch" /></template>
