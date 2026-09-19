<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsjob7bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rsjob7bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:round-struck" /></template>
