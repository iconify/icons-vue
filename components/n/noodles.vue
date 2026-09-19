<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqvv9mw1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqvv9mw1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:noodles" /></template>
