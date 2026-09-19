<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsl62v89g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wsl62v89g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-plain-fill-12" /></template>
