<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_2t2kgv.css';
import '../../css/w/w9r2jnnqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri_2t2kgv"/><path class="w9r2jnnqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:twospeechbubbles" /></template>
