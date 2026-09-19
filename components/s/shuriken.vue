<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3s75fbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3s75fbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shuriken" /></template>
