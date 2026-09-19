<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji_aadxel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ji_aadxel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:speedometer" /></template>
