<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofvr41bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ofvr41bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sundial" /></template>
