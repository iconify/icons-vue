<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivti-ab3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivti-ab3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:terminal-sharp" /></template>
