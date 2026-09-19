<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzvh-ba9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qzvh-ba9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:watering-can" /></template>
