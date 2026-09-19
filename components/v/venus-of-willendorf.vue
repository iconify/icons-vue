<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd86mdi0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pd86mdi0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:venus-of-willendorf" /></template>
