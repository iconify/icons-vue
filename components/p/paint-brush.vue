<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kohcfm9fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kohcfm9fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paint-brush" /></template>
