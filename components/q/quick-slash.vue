<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f75bf_bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f75bf_bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:quick-slash" /></template>
