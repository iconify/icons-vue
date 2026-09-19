<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7pudyz4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h7pudyz4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:needle-drill" /></template>
