<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ube0iz5zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ube0iz5zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-question-small-filled" /></template>
