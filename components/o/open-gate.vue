<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whhsbdc7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whhsbdc7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:open-gate" /></template>
