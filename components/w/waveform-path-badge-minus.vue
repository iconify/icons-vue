<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moc26lgsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="moc26lgsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:waveform-path-badge-minus" /></template>
