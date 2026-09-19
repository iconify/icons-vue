<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu8-jub8h.css';
import '../../css/m/m0eb90q8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cu8-jub8h"/><path class="m0eb90q8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-lightning-bolt-stroke-12" /></template>
