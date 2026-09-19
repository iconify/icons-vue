<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn11h8yys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bn11h8yys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:winter-gloves" /></template>
