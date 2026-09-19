<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzsr2-b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzsr2-b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trash-can" /></template>
