<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wva8ckbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wva8ckbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:matchbox" /></template>
