<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc0-x-b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vc0-x-b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:target-laser" /></template>
