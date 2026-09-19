<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euaaxfogw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="euaaxfogw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rolling-dices" /></template>
