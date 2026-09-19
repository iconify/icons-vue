<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhv3vqb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhv3vqb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:save" /></template>
