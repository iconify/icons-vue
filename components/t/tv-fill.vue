<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvsmmt4aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qvsmmt4aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tv-fill" /></template>
