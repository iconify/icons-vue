<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5gk22b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d5gk22b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-conversation-fill-12" /></template>
