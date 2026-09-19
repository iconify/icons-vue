<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqo9k340o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqo9k340o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tumbleweed" /></template>
