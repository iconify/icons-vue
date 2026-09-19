<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tib28zb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tib28zb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ringing-alarm" /></template>
