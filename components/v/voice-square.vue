<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_o52bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj_o52bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:voice-square" /></template>
