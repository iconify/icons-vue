<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klpdtzbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="klpdtzbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-typing-fill-12" /></template>
