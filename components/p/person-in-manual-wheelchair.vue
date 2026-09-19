<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp9wi3bpj.css';
import '../../css/i/ie7lpxbir.css';
import '../../css/q/qpr0x4hrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zp9wi3bpj"/><path class="ie7lpxbir"/><path class="qpr0x4hrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-in-manual-wheelchair" /></template>
