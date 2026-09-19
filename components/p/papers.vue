<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx2qpccww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx2qpccww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:papers" /></template>
