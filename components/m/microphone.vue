<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai8j3lypx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ai8j3lypx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:microphone" /></template>
