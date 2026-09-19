<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qip-qnboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qip-qnboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:twirly-flower" /></template>
