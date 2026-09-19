<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu022rzoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uu022rzoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-typing-fill-16" /></template>
