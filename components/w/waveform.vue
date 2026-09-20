<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvt6bnbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tvt6bnbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:waveform" /></template>
