<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0_f5vtuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h0_f5vtuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:round-bottom-flask" /></template>
