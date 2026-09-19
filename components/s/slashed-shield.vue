<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k78kfq9cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k78kfq9cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slashed-shield" /></template>
