<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwuo8mbhr.css';
import '../../css/t/t37b9jb9z.css';
import '../../css/q/qh6npjbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qwuo8mbhr"/><path class="t37b9jb9z"/><path class="qh6npjbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-48" /></template>
