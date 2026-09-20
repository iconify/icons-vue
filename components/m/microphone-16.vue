<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4ph5-szq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4ph5-szq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:microphone-16" /></template>
