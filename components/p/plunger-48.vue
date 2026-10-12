<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqsth4bzo.css';
import '../../css/l/linospgqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yqsth4bzo"/><path class="linospgqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plunger-48" /></template>
