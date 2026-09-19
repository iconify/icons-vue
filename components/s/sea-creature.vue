<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvem7lbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvem7lbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sea-creature" /></template>
