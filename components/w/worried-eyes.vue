<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds1i_q67m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds1i_q67m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:worried-eyes" /></template>
