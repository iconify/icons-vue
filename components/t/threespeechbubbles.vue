<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-4ziq31h.css';
import '../../css/o/o7-5ytbma.css';
import '../../css/n/n2e31kbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-4ziq31h"/><path class="o7-5ytbma"/><path class="n2e31kbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:threespeechbubbles" /></template>
