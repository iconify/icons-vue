<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyk6yzhpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyk6yzhpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sergeant" /></template>
