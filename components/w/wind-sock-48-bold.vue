<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l359dqins.css';
import '../../css/d/dcw38u4hx.css';
import '../../css/f/f7u3lacne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l359dqins"/><path class="dcw38u4hx"/><path class="f7u3lacne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-sock-48-bold" /></template>
