<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx3c_8b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rx3c_8b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rosa-shield" /></template>
