<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coowa9bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coowa9bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:speech-bubble-quote-solid-expressive" /></template>
