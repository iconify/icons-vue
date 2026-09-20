<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kklh9cc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kklh9cc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-lounge-dark" /></template>
