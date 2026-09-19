<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glclllbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glclllbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sharp-lips" /></template>
