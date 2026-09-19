<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o24996cza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o24996cza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:radar-sweep" /></template>
