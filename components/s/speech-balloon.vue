<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw3g69bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iw3g69bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:speech-balloon" /></template>
