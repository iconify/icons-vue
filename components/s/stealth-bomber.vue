<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdkq10bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdkq10bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stealth-bomber" /></template>
