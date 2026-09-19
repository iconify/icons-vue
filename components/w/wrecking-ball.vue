<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj-4mebdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pj-4mebdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wrecking-ball" /></template>
