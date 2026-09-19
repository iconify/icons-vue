<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wob2l3rnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wob2l3rnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:open-panel-filled-top" /></template>
