<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fccpd3bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fccpd3bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:web-spit" /></template>
