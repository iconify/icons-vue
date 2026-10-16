<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvfjtltty.css';
import '../../css/l/livgcivqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hvfjtltty"/><path class="livgcivqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mailbox-48-bold" /></template>
