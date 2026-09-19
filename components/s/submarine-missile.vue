<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qacw4q04o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qacw4q04o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:submarine-missile" /></template>
