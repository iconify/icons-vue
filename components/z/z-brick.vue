<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyuim9bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hyuim9bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:z-brick" /></template>
