<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-gp98b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-gp98b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:waves" /></template>
