<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1m46ir4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l1m46ir4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:volume-mute-remix" /></template>
