<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clzusyb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="clzusyb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:noodle-ball" /></template>
