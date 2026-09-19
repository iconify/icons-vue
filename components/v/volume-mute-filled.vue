<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni98h0b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ni98h0b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-mute-filled" /></template>
