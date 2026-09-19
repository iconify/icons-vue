<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkx2bjwdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kkx2bjwdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-conversation-stroke-12" /></template>
