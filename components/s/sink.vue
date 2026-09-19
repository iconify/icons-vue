<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjl8s6b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mjl8s6b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sink" /></template>
