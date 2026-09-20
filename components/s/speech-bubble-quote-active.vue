<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1mvvxb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1mvvxb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:speech-bubble-quote-active" /></template>
