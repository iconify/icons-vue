<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tphb67bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tphb67bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:split-cross" /></template>
