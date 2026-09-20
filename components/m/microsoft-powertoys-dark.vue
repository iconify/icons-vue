<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn776wbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jn776wbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powertoys-dark" /></template>
